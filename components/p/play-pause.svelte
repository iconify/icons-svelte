<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ridyy-8nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ridyy-8nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:play-pause" {...props}></Icon>
