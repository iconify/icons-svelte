<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv0437bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="pv0437bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:map-pin" {...props}></Icon>
