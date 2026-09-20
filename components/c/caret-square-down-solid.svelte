<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/copc66w9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="copc66w9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:caret-square-down-solid" {...props}></Icon>
