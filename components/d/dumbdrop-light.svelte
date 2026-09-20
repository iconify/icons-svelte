<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvimtok6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vvimtok6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbdrop-light" {...props}></Icon>
