<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpuk8e8pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xpuk8e8pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:brush" {...props}></Icon>
