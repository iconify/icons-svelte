<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j427dzbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j427dzbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-backup-service-vpc" {...props}></Icon>
