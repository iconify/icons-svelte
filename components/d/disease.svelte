<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isq-m5t3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isq-m5t3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:disease" {...props}></Icon>
