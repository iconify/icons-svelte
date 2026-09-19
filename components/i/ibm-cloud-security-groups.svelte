<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpn-fce2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fpn-fce2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-security-groups" {...props}></Icon>
