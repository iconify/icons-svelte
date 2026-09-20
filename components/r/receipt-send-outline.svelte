<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjxy9soza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjxy9soza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt-send-outline" {...props}></Icon>
