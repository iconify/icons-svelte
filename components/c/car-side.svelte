<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpdpv0b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="mpdpv0b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:car-side" {...props}></Icon>
