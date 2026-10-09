<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r39i0s06f.css';
import '../../css/m/muoqy1bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r39i0s06f"/><path class="muoqy1bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:newspaper-20-bold" {...props}></Icon>
