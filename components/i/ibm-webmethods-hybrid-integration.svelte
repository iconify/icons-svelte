<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urjbm3bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="urjbm3bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-webmethods-hybrid-integration" {...props}></Icon>
