<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuy1robfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wuy1robfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:algolia" {...props}></Icon>
