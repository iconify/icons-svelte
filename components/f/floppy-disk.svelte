<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh_mbgb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fh_mbgb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:floppy-disk" {...props}></Icon>
