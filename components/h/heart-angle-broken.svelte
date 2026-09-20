<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2ab7w3yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2ab7w3yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-angle-broken" {...props}></Icon>
