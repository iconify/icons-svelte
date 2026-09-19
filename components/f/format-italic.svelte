<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3bsp4s4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="e3bsp4s4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-italic" {...props}></Icon>
