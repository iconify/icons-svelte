<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqhzgwb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqhzgwb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:luggage-cart-fill" {...props}></Icon>
