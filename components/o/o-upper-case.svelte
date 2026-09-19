<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw1s4i0cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":794,"height":775};
const content = `<path class="fw1s4i0cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:o-upper-case" {...props}></Icon>
