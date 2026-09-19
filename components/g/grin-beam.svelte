<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp2g8gjga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="tp2g8gjga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grin-beam" {...props}></Icon>
