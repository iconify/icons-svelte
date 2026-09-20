<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzun-2b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzun-2b7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt-text-check-outline" {...props}></Icon>
