<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9o1olbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e9o1olbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:flip" {...props}></Icon>
