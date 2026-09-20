<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrs2_fwzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wrs2_fwzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:attachment-upload" {...props}></Icon>
