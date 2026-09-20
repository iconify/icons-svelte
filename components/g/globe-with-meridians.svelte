<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz-_5oksg.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/u/usozxnbrm.css';
import '../../css/y/y4f-t_i2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="sz-_5oksg"/><g class="ij2x_72vy"><circle class="usozxnbrm"/><path class="y4f-t_i2z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:globe-with-meridians" {...props}></Icon>
