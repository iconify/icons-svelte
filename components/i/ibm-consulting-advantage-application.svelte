<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e98t4kbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e98t4kbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-consulting-advantage-application" {...props}></Icon>
