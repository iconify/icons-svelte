<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwnz-qbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jwnz-qbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:magic-wand-and-sparkles" {...props}></Icon>
