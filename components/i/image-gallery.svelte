<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5ct9tbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i5ct9tbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:image-gallery" {...props}></Icon>
