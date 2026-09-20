<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4v4omber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w4v4omber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:palfed" {...props}></Icon>
