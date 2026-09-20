<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvmh88bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fvmh88bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chart-curve-linear" {...props}></Icon>
