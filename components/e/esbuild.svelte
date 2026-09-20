<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0r-2x1bp.css';
import '../../css/m/m7mjk89gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<circle class="f0r-2x1bp"/><path class="m7mjk89gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:esbuild" {...props}></Icon>
