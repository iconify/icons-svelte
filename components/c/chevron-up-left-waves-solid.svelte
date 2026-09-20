<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt-qhfbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt-qhfbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up-left-waves-solid" {...props}></Icon>
