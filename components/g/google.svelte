<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq-4k7bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zq-4k7bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:google" {...props}></Icon>
