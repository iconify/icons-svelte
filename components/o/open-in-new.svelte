<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw_57bbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="dw_57bbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:open-in-new" {...props}></Icon>
