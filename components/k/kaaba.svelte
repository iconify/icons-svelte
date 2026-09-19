<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5ectfbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="f5ectfbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:kaaba" {...props}></Icon>
