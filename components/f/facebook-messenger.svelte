<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5zp_6bpu.css';
import '../../css/y/ynlpaobkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5zp_6bpu"/><path class="ynlpaobkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:facebook-messenger" {...props}></Icon>
