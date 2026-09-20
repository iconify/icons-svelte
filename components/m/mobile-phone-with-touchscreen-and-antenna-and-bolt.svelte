<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqsabwbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lqsabwbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mobile-phone-with-touchscreen-and-antenna-and-bolt" {...props}></Icon>
