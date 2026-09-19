<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i14apub5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i14apub5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-mm" {...props}></Icon>
