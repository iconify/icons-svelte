<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcqr4nb2y.css';
import '../../css/a/aruuerbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zcqr4nb2y"/><path class="aruuerbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:headlamp" {...props}></Icon>
