<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-w8v3b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="l-w8v3b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:goodreads" {...props}></Icon>
