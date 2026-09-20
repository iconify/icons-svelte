<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in5wtwq8h.css';
import '../../css/t/tbzab391z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="in5wtwq8h"/><path class="tbzab391z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:red-square" {...props}></Icon>
