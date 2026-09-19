<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn7_n2bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cn7_n2bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bell-concierge" {...props}></Icon>
