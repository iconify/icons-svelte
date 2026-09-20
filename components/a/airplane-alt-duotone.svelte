<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cgd6e8bux.css';
import '../../css/s/s9yq6kdnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cgd6e8bux"/><path class="s9yq6kdnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:airplane-alt-duotone" {...props}></Icon>
