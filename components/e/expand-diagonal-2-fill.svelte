<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll0vpnbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll0vpnbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-diagonal-2-fill" {...props}></Icon>
