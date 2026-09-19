<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwjzqebfb.css';
import '../../css/e/e4snvjyzq.css';
import '../../css/o/oh_sxl0hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kwjzqebfb"/><path class="e4snvjyzq"/><path class="oh_sxl0hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hl7-attributes" {...props}></Icon>
