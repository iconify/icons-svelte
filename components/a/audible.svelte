<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq7aiob3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xq7aiob3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:audible" {...props}></Icon>
