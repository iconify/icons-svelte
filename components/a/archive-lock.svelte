<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x08vkdwor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x08vkdwor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-lock" {...props}></Icon>
