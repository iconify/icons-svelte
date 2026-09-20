<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh8gqdp9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh8gqdp9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:phone-camera-line" {...props}></Icon>
