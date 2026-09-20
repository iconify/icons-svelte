<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bflgrf8bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bflgrf8bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:atm-14" {...props}></Icon>
