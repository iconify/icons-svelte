<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axfuvnbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="axfuvnbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:frowning-face-with-head-bandage" {...props}></Icon>
