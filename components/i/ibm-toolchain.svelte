<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_wq1vbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a_wq1vbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-toolchain" {...props}></Icon>
