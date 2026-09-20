<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m61z8jb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m61z8jb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-50-bluetooth" {...props}></Icon>
