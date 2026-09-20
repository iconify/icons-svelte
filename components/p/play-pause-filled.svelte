<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2vub05sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k2vub05sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:play-pause-filled" {...props}></Icon>
