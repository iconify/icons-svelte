<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kamgprbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kamgprbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:arrow-back-circle" {...props}></Icon>
