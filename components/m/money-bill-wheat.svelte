<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei56k7b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ei56k7b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:money-bill-wheat" {...props}></Icon>
