<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxrt52mwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fxrt52mwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:question-mark-on-square" {...props}></Icon>
