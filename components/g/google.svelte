<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc1lwwb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fc1lwwb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:google" {...props}></Icon>
