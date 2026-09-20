<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehqakfbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ehqakfbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:eye-cancelled" {...props}></Icon>
