<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isv9qth2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="isv9qth2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-natural-language-classifier" {...props}></Icon>
