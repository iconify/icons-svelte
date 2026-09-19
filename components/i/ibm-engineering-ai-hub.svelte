<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eywq5cbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eywq5cbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-engineering-ai-hub" {...props}></Icon>
