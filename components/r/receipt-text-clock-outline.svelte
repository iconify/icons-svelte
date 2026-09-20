<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl11uwbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl11uwbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt-text-clock-outline" {...props}></Icon>
