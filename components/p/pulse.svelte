<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd5p1nvyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="jd5p1nvyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pulse" {...props}></Icon>
