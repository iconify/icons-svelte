<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swqrgmbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="swqrgmbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-bold" {...props}></Icon>
