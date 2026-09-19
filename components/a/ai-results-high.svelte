<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw3u8dcyu.css';
import '../../css/s/s3bjnib6t.css';
import '../../css/c/cytj3kbqo.css';
import '../../css/a/a574bcccz.css';
import '../../css/q/qnmiannsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rw3u8dcyu"/><path class="s3bjnib6t"/><path class="cytj3kbqo"/><path class="a574bcccz"/><path class="qnmiannsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-results-high" {...props}></Icon>
