<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlbmz9bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlbmz9bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hamburger-off" {...props}></Icon>
