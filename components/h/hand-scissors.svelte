<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r74fw468h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="r74fw468h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:hand-scissors" {...props}></Icon>
