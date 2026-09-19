<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/h/hj7z5ybgc.css';
import '../../css/r/refdwsb5n.css';
import '../../css/i/i1t1lgbyt.css';
import '../../css/b/bp1du6igj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="hj7z5ybgc"/><path class="refdwsb5n"/><path class="i1t1lgbyt"/><path class="bp1du6igj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:donate" {...props}></Icon>
