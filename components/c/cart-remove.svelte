<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6bxe_0no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6bxe_0no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cart-remove" {...props}></Icon>
