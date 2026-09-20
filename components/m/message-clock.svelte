<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5af0rbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5af0rbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:message-clock" {...props}></Icon>
