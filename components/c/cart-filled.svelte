<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whjp1dbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whjp1dbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cart-filled" {...props}></Icon>
