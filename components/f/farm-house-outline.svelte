<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfw4fsb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfw4fsb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:farm-house-outline" {...props}></Icon>
