<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_dl_z0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gp_dl_z0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:neutral-face-in-circle" {...props}></Icon>
