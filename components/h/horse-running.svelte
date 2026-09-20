<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9-xbkb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p9-xbkb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:horse-running" {...props}></Icon>
