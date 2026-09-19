<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9i1nc98d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="u9i1nc98d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:replay-10" {...props}></Icon>
