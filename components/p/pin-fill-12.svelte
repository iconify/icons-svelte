<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1yn-jb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y1yn-jb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pin-fill-12" {...props}></Icon>
