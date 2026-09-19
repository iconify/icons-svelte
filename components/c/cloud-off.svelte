<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc_upz09w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":408};
const content = `<path class="kc_upz09w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cloud-off" {...props}></Icon>
