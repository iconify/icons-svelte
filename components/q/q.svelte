<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p83c6_bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="p83c6_bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:q" {...props}></Icon>
