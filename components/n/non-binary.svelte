<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slfsep4xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="slfsep4xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:non-binary" {...props}></Icon>
