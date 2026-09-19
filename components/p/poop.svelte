<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw-zgv1oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mw-zgv1oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:poop" {...props}></Icon>
