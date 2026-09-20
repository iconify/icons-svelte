<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azkx3ab1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="azkx3ab1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bible" {...props}></Icon>
