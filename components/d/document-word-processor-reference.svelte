<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebby860qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ebby860qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-word-processor-reference" {...props}></Icon>
