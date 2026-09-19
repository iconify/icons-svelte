<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sftnd-fer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sftnd-fer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-partner-plus" {...props}></Icon>
