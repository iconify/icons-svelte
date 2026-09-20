<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd83ysbnr.css';
import '../../css/t/t58dp5a-u.css';
import '../../css/y/y_g4h7d1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="bd83ysbnr"/><path class="t58dp5a-u"/><path class="y_g4h7d1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:japanese-symbol-for-beginner" {...props}></Icon>
