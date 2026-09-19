<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mabl9iovh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mabl9iovh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:controls-volumeon" {...props}></Icon>
