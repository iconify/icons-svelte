<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7_5l5l3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c7_5l5l3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-beside-oval-broadleaved-tree-above-water" {...props}></Icon>
