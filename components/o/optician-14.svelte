<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beljj4eyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="beljj4eyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:optician-14" {...props}></Icon>
