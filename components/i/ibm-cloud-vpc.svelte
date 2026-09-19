<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz4qtlb3x.css';
import '../../css/g/glzb1mbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xz4qtlb3x"/><path class="glzb1mbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-vpc" {...props}></Icon>
