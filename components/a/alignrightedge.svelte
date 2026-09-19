<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_gz1s1cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c_gz1s1cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alignrightedge" {...props}></Icon>
