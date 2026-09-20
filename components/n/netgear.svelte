<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_mglgxaq.css';
import '../../css/p/p-_y-_-ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_mglgxaq"/><path class="p-_y-_-ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netgear" {...props}></Icon>
