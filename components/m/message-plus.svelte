<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6nl6hbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6nl6hbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:message-plus" {...props}></Icon>
