<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix3_ozt3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ix3_ozt3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:drop" {...props}></Icon>
