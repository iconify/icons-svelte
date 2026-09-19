<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zk_skwi6v.css';
import '../../css/p/pvyxalenk.css';
import '../../css/h/h5_6wb9kx.css';
import '../../css/s/s3-pvbj0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zk_skwi6v"/><path class="pvyxalenk"/><path class="h5_6wb9kx"/><path clip-rule="evenodd" class="s3-pvbj0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-stand-middle-bold" {...props}></Icon>
