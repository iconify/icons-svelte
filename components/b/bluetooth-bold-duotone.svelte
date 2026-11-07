<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg5mtsbge.css';
import '../../css/e/eiwc-7x-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kg5mtsbge"/><path class="eiwc-7x-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bluetooth-bold-duotone" {...props}></Icon>
