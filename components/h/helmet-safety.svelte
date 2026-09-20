<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqc_swu4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tqc_swu4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:helmet-safety" {...props}></Icon>
