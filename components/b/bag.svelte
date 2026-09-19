<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spdolhb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="spdolhb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bag" {...props}></Icon>
