<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsin-x7co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zsin-x7co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:binoculars-filled" {...props}></Icon>
