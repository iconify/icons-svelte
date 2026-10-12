<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_dv-4xcr.css';
import '../../css/h/hxy_y1dfx.css';
import '../../css/z/z_aw5vbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d_dv-4xcr"/><path class="hxy_y1dfx"/><path class="z_aw5vbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-lock-20" {...props}></Icon>
