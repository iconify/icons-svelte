<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg9bjcbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg9bjcbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-fast-outline" {...props}></Icon>
