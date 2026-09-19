<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz9k_iy5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tz9k_iy5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:infinity" {...props}></Icon>
