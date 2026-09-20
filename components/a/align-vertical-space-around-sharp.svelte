<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfkwqpsmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfkwqpsmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-vertical-space-around-sharp" {...props}></Icon>
