<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4uiyxbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4uiyxbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:contactless-payment-circle-outline" {...props}></Icon>
