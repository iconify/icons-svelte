<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2ji2r33e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t2ji2r33e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:envelope-open-fill" {...props}></Icon>
