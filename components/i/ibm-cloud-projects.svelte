<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt-jlzwbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vt-jlzwbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-projects" {...props}></Icon>
