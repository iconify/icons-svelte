<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8hhtkv4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p8hhtkv4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-security" {...props}></Icon>
