<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxxl__0bs.css';
import '../../css/e/e4ngkd7is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zxxl__0bs"/><path class="e4ngkd7is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:brush" {...props}></Icon>
