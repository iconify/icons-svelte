<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhsj9o-gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="xhsj9o-gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:map-alt-3-filled" {...props}></Icon>
