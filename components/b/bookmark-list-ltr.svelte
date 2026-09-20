<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqvk4veur.css';
import '../../css/a/a1ey-7bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zqvk4veur"/><path class="a1ey-7bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bookmark-list-ltr" {...props}></Icon>
