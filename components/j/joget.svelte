<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps5o6mbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ps5o6mbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:joget" {...props}></Icon>
