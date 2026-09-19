<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl8z71bau.css';
import '../../css/y/yfddwd_7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cl8z71bau"/><path class="yfddwd_7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-service-management" {...props}></Icon>
