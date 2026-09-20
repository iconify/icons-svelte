<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpul06c7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpul06c7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt-text-minus-outline" {...props}></Icon>
