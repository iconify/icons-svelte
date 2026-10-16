<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8irp8b8i.css';
import '../../css/u/ur2a2fbgl.css';
import '../../css/x/x3jkzl--z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r8irp8b8i"/><path class="ur2a2fbgl"/><path class="x3jkzl--z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-fryer-20-bold" {...props}></Icon>
