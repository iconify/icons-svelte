<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c04ix1e3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="c04ix1e3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-16" {...props}></Icon>
