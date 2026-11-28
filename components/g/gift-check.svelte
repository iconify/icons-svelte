<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb1q9l_xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb1q9l_xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:gift-check" {...props}></Icon>
