<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3flw9_uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3flw9_uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:magnify-remove-cursor" {...props}></Icon>
