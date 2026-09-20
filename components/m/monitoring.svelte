<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmtqhdb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wmtqhdb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:monitoring" {...props}></Icon>
