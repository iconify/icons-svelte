<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg5u4cbcz.css';
import '../../css/i/ictwwwp8x.css';
import '../../css/l/lc3doybli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="xg5u4cbcz"/><path class="ictwwwp8x"/><path class="lc3doybli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:bq-4x3" {...props}></Icon>
