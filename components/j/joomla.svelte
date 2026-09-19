<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9fy_5bev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i9fy_5bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:joomla" {...props}></Icon>
