<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzp-m6bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rzp-m6bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-playstore" {...props}></Icon>
