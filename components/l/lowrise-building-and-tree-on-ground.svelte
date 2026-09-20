<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py8_zzozw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="py8_zzozw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lowrise-building-and-tree-on-ground" {...props}></Icon>
