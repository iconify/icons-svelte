<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfyj5vbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sfyj5vbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-code-engine" {...props}></Icon>
