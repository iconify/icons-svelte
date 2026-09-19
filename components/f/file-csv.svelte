<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1pj1tb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d1pj1tb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-csv" {...props}></Icon>
