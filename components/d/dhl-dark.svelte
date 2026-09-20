<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsbxedbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fsbxedbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dhl-dark" {...props}></Icon>
