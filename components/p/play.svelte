<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5_h21b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j5_h21b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:play" {...props}></Icon>
