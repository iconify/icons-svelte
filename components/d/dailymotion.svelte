<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_32gz_1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="e_32gz_1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:dailymotion" {...props}></Icon>
