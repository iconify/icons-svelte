<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkuxgfblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bkuxgfblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:car-filled" {...props}></Icon>
