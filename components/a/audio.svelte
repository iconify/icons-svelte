<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g66k8eb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g66k8eb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:audio" {...props}></Icon>
