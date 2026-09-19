<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfx_ymb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yfx_ymb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bowling-ball" {...props}></Icon>
