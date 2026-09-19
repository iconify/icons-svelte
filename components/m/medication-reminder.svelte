<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvis7qbvb.css';
import '../../css/s/s9ppw9blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uvis7qbvb"/><circle class="s9ppw9blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:medication-reminder" {...props}></Icon>
