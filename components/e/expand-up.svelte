<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbnktsb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mbnktsb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:expand-up" {...props}></Icon>
