<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbl65ebhc.css';
import '../../css/o/opemywb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dbl65ebhc"/><path class="opemywb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bed-20-bold" {...props}></Icon>
