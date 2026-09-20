<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js1dubcgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js1dubcgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt-text-arrow-right-outline" {...props}></Icon>
