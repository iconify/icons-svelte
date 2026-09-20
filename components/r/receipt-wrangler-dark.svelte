<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4omcobro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z4omcobro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:receipt-wrangler-dark" {...props}></Icon>
