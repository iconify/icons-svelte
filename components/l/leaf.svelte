<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzry2ab_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lzry2ab_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:leaf" {...props}></Icon>
