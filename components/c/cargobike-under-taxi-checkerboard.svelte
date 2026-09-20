<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7wv62--d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i7wv62--d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cargobike-under-taxi-checkerboard" {...props}></Icon>
