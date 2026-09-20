<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbr59b2hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fbr59b2hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:open-external" {...props}></Icon>
