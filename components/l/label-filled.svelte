<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmz2_w97h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qmz2_w97h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:label-filled" {...props}></Icon>
