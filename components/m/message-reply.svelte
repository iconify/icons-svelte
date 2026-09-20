<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa25j04aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa25j04aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:message-reply" {...props}></Icon>
