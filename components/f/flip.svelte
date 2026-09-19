<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4hx52bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":480};
const content = `<path class="k4hx52bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flip" {...props}></Icon>
