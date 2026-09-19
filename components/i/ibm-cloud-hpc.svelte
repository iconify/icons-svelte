<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7ncarbqz.css';
import '../../css/x/xm09adb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c7ncarbqz"/><path class="xm09adb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-hpc" {...props}></Icon>
