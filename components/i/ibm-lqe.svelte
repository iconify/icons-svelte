<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptz7ttbgp.css';
import '../../css/d/dlkylf--k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ptz7ttbgp"/><path class="dlkylf--k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-lqe" {...props}></Icon>
