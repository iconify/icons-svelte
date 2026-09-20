<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw3ccs95k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xw3ccs95k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bowling-pin" {...props}></Icon>
