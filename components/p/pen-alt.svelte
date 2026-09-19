<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw5rx_s2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zw5rx_s2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:pen-alt" {...props}></Icon>
