<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5_sz-bgs.css';
import '../../css/b/b86mn5bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p5_sz-bgs"/><path class="b86mn5bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bridge-20-bold" {...props}></Icon>
