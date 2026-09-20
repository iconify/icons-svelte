<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s00ripn2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="s00ripn2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:one-finger-drag-horizontal" {...props}></Icon>
