<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-s0w9hal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x-s0w9hal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:plus-circle" {...props}></Icon>
