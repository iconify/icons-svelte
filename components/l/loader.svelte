<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/bg2fqfxmz.css';
import '../../css/q/q_h3vjbce.css';
import '../../css/c/co_a6dbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="bg2fqfxmz wm-shadow"/><path class="q_h3vjbce wm-shadow"/><path class="co_a6dbew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:loader" {...props}></Icon>
