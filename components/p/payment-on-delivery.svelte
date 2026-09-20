<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln6t6pbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln6t6pbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:payment-on-delivery" {...props}></Icon>
