<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i__a2hb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="i__a2hb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:jstor-square" {...props}></Icon>
