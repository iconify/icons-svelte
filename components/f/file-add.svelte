<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak2lr7bfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="ak2lr7bfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:file-add" {...props}></Icon>
