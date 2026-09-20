<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/levtbqbbg.css';
import '../../css/c/c_o0h-edl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="levtbqbbg"/><path class="c_o0h-edl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:reverse-button" {...props}></Icon>
