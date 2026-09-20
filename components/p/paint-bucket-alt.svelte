<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpp_p0b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vpp_p0b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:paint-bucket-alt" {...props}></Icon>
