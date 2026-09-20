<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6d9f0b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g6d9f0b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:glass-whiskey" {...props}></Icon>
