<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c2tm5x4ew.css';
import '../../css/x/x1m0prbrb.css';
import '../../css/d/d3t_gac1b.css';
import '../../css/n/n8_pa2b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c2tm5x4ew"/><path class="x1m0prbrb"/><path class="d3t_gac1b"/><path class="n8_pa2b5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:audio" {...props}></Icon>
