<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldlei_y_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="ldlei_y_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cloud-outline-alt" {...props}></Icon>
