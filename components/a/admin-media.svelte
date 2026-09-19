<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvy4j9bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yvy4j9bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-media" {...props}></Icon>
