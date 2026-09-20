<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3368wbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r3368wbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:frowning-face-with-head-bandage-in-circle" {...props}></Icon>
