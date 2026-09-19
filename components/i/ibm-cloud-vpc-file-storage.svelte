<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4_pv09me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w4_pv09me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-vpc-file-storage" {...props}></Icon>
