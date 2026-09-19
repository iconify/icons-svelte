<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wc2k_3bib.css';
import '../../css/f/f_5j5hbbh.css';
import '../../css/y/yn91wp2qf.css';
import '../../css/h/ho6q2_ixk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="wc2k_3bib"/><rect class="f_5j5hbbh"/><rect class="yn91wp2qf"/><rect class="ho6q2_ixk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:ellipsis-circle" {...props}></Icon>
