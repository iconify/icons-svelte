<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-3fxs8ew.css';
import '../../css/y/yhn66eyul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="p-3fxs8ew"/><path class="yhn66eyul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:part-alternation-mark" {...props}></Icon>
