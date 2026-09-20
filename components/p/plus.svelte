<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydnyoo1kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ydnyoo1kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plus" {...props}></Icon>
