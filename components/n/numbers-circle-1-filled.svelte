<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv_r-fwua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vv_r-fwua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-circle-1-filled" {...props}></Icon>
