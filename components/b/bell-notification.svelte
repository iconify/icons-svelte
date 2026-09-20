<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcuq8jb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcuq8jb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-notification" {...props}></Icon>
