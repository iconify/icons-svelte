<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz-ym6b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xz-ym6b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:reservation-orders" {...props}></Icon>
