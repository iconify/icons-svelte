<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij2x_72vy.css';
import '../../css/i/ilr6hpbnj.css';
import '../../css/p/pcurjzbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="ij2x_72vy"><path class="ilr6hpbnj"/><path class="pcurjzbpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:forward" {...props}></Icon>
