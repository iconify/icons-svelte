<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmj1jdbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cmj1jdbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-up-to-ticket-in-slot" {...props}></Icon>
