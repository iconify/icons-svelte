<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot1pakbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ot1pakbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:magnifying-glass" {...props}></Icon>
