<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-bf3xbdx.css';
import '../../css/z/zmolltb3u.css';
import '../../css/a/a_mixmbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="z-bf3xbdx"/><path class="zmolltb3u"/><path class="a_mixmbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:es-pv-4x3" {...props}></Icon>
