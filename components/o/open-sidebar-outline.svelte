<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtcb-ccwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtcb-ccwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:open-sidebar-outline" {...props}></Icon>
