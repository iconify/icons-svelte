<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j68inccny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j68inccny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watsonx-code-assistant-for-z-understand" {...props}></Icon>
