<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyz1-gphb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cyz1-gphb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-software-watsonx-data-unstructured-import" {...props}></Icon>
