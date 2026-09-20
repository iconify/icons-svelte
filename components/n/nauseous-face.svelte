<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmlxr4bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zmlxr4bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:nauseous-face" {...props}></Icon>
