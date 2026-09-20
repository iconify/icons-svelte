<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5d9xcp3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t5d9xcp3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:paifang" {...props}></Icon>
