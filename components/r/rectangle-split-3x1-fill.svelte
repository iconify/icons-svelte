<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc0ak45iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="cc0ak45iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-split-3x1-fill" {...props}></Icon>
