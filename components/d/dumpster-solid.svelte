<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmn4a1b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fmn4a1b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dumpster-solid" {...props}></Icon>
