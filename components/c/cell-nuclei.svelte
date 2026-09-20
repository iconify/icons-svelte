<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6oz_hz0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i6oz_hz0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cell-nuclei" {...props}></Icon>
