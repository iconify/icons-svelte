<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sssou3bkf.css';
import '../../css/y/ybhu5ybua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sssou3bkf"/><path class="ybhu5ybua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-pal" {...props}></Icon>
