<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bls5yhbwz.css';
import '../../css/r/r7vl_0u4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bls5yhbwz"/><path class="r7vl_0u4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:outage-map-20-bold" {...props}></Icon>
