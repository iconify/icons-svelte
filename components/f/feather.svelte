<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp3-tgj1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yp3-tgj1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:feather" {...props}></Icon>
