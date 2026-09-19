<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwv4w0b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cwv4w0b7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:burger" {...props}></Icon>
