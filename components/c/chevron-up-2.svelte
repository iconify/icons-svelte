<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqwc4tbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqwc4tbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chevron-up-2" {...props}></Icon>
