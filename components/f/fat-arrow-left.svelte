<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8_3b8ifa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8_3b8ifa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-arrow-left" {...props}></Icon>
