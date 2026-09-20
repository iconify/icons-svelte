<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6s1d5urq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="d6s1d5urq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-8" {...props}></Icon>
