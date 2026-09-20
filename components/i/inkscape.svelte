<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bns68ccvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bns68ccvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:inkscape" {...props}></Icon>
