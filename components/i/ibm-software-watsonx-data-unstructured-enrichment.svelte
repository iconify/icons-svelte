<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efac48boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="efac48boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-software-watsonx-data-unstructured-enrichment" {...props}></Icon>
