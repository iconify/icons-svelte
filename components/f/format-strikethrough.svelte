<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs-twgpig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs-twgpig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-strikethrough" {...props}></Icon>
