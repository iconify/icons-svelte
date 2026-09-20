<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skjtd3mxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="skjtd3mxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-import-solid" {...props}></Icon>
