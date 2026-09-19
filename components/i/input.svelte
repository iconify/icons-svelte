<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgb1p3bxd.css';
import '../../css/r/rlnza7pox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fgb1p3bxd"/><path class="rlnza7pox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:input" {...props}></Icon>
