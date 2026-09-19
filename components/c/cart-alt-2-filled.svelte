<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru0p89b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru0p89b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cart-alt-2-filled" {...props}></Icon>
