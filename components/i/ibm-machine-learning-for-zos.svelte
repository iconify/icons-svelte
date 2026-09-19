<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd-dkvbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yd-dkvbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-machine-learning-for-zos" {...props}></Icon>
