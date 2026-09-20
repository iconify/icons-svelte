<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfjl8bbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfjl8bbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:calendar" {...props}></Icon>
