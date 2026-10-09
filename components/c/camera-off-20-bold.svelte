<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buk4h-b4t.css';
import '../../css/o/om5drtboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="buk4h-b4t"/><path class="om5drtboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-off-20-bold" {...props}></Icon>
