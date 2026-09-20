<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs4-vbmfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xs4-vbmfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coral" {...props}></Icon>
