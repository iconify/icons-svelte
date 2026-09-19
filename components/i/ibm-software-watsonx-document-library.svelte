<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-hgkmbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y-hgkmbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-software-watsonx-document-library" {...props}></Icon>
