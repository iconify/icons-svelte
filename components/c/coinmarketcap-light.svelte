<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy1olh6cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fy1olh6cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coinmarketcap-light" {...props}></Icon>
