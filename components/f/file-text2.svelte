<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnk1gt9lb.css';
import '../../css/c/c66w0quot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xnk1gt9lb"/><path class="c66w0quot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:file-text2" {...props}></Icon>
