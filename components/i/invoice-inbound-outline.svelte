<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqi838r2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqi838r2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-inbound-outline" {...props}></Icon>
