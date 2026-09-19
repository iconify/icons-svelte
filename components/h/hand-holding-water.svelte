<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg-14ob0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="eg-14ob0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hand-holding-water" {...props}></Icon>
