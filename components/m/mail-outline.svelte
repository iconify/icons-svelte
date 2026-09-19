<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4gmmqchl.css';
import '../../css/r/rhqsj1c8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="k4gmmqchl"/><path class="rhqsj1c8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:mail-outline" {...props}></Icon>
