<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfd52pbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfd52pbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hourglass-fill-round" {...props}></Icon>
