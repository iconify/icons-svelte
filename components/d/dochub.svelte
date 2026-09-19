<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6--woh2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":512};
const content = `<path class="b6--woh2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:dochub" {...props}></Icon>
