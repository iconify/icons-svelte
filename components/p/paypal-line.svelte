<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc5lombzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc5lombzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:paypal-line" {...props}></Icon>
