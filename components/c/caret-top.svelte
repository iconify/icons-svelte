<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llpghbi5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="llpghbi5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:caret-top" {...props}></Icon>
