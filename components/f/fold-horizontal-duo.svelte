<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/brizay85j.css';
import '../../css/l/lk6j99brh.css';
import '../../css/e/e3o5kybty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="brizay85j"/><path class="lk6j99brh"/><path class="e3o5kybty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fold-horizontal-duo" {...props}></Icon>
