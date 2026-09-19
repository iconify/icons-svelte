<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuwmmiujp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuwmmiujp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cart-check-filled" {...props}></Icon>
