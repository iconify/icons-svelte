<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2n7uvblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="f2n7uvblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:hat-man-filled" {...props}></Icon>
