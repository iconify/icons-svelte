<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmot0ebfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmot0ebfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cart-plus-filled" {...props}></Icon>
