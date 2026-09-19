<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2mgj9h3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k2mgj9h3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-test-accelerator-for-z" {...props}></Icon>
