<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atzp2n7qu.css';
import '../../css/y/yp-w5kbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atzp2n7qu"/><path clip-rule="evenodd" class="yp-w5kbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-4-bold" {...props}></Icon>
