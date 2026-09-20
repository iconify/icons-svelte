<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewowm-bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewowm-bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:android" {...props}></Icon>
