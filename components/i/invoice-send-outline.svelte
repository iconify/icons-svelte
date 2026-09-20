<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiwlsmqbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uiwlsmqbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-send-outline" {...props}></Icon>
