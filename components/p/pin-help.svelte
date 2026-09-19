<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcni0tkfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":456};
const content = `<path class="hcni0tkfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:pin-help" {...props}></Icon>
