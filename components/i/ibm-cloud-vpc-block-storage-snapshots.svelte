<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3jzubbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y3jzubbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-vpc-block-storage-snapshots" {...props}></Icon>
