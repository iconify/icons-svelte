<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_3x2pb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e_3x2pb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down-from-payment-card-in-slot" {...props}></Icon>
