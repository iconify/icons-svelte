<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpt1l0w-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jpt1l0w-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:payment-card-in-slot" {...props}></Icon>
