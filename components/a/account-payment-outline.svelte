<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ana4hn6qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ana4hn6qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-payment-outline" {...props}></Icon>
