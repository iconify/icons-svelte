<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsnbwd4wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsnbwd4wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:message-arrow-right" {...props}></Icon>
