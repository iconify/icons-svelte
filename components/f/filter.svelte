<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/raf3v2b9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="raf3v2b9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:filter" {...props}></Icon>
