<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpg1m5ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpg1m5ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-center-vertical-fill-round" {...props}></Icon>
