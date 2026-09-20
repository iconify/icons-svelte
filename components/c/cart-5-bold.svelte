<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b918qp0xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b918qp0xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-5-bold" {...props}></Icon>
