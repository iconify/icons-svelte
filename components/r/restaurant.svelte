<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1de7ob0p.css';
import '../../css/f/fi8p1vbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i1de7ob0p"/><path class="fi8p1vbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:restaurant" {...props}></Icon>
