<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmu515hrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fmu515hrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:critical-role" {...props}></Icon>
