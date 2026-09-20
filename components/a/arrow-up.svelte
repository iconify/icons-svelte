<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpny1ho_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qpny1ho_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:arrow-up" {...props}></Icon>
