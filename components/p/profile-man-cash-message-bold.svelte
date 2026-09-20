<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w70p-uwcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w70p-uwcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:profile-man-cash-message-bold" {...props}></Icon>
