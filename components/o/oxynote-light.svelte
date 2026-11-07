<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi_ebxbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pi_ebxbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oxynote-light" {...props}></Icon>
