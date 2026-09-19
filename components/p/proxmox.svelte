<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqsa_mblk.css';
import '../../css/c/cx1y_wb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qqsa_mblk"/><path class="cx1y_wb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:proxmox" {...props}></Icon>
