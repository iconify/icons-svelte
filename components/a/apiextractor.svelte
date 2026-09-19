<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz5zt-bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":435,"height":512};
const content = `<path class="nz5zt-bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:apiextractor" {...props}></Icon>
