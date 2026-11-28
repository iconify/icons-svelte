<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuoycacsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuoycacsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cart-check" {...props}></Icon>
