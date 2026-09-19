<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djmor1xwt.css';
import '../../css/r/r0dndstuf.css';
import '../../css/s/s6u7mybjl.css';
import '../../css/z/zc3_-gfsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="djmor1xwt"/><path class="r0dndstuf"/><path class="s6u7mybjl"/><path class="zc3_-gfsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:rect" {...props}></Icon>
