<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4_ukxvxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k4_ukxvxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:center-horizontally-filled" {...props}></Icon>
