<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu82nqowe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zu82nqowe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rare-earth-20-bold" {...props}></Icon>
