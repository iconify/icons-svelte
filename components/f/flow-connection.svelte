<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfchu_-gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rfchu_-gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flow-connection" {...props}></Icon>
