<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5_huo6_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k5_huo6_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aiostreams-light" {...props}></Icon>
