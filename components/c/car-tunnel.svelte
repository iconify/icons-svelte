<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-m5keb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f-m5keb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:car-tunnel" {...props}></Icon>
