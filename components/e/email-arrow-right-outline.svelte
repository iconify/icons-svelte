<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc30tubfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc30tubfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-arrow-right-outline" {...props}></Icon>
