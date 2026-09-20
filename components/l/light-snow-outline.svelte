<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-opy4b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z-opy4b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:light-snow-outline" {...props}></Icon>
