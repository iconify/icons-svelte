<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1t1o_btq.css';
import '../../css/r/r-v6gebze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1t1o_btq"/><path class="r-v6gebze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:location-pin" {...props}></Icon>
