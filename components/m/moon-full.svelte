<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urm15cc8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="urm15cc8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-full" {...props}></Icon>
