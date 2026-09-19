<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4_b-eaap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t4_b-eaap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-software-watsonx-data-analyze-and-process" {...props}></Icon>
