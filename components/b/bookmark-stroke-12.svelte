<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp02h-b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pp02h-b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bookmark-stroke-12" {...props}></Icon>
