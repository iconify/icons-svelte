<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb_xwzbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="pb_xwzbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-indent-decrease" {...props}></Icon>
