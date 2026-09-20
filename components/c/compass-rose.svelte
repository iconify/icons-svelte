<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4g1111yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b4g1111yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:compass-rose" {...props}></Icon>
