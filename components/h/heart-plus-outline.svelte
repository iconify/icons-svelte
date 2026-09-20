<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka1t0xb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka1t0xb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-plus-outline" {...props}></Icon>
