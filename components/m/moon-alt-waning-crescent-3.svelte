<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbnww1biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="cbnww1biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waning-crescent-3" {...props}></Icon>
