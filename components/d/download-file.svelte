<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/om8ne5bsn.css';
import '../../css/v/vp5lb0bdv.css';
import '../../css/a/ajvscq4iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="om8ne5bsn"/><path class="vp5lb0bdv"/><path class="ajvscq4iy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:download-file" {...props}></Icon>
