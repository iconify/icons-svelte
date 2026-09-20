<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhys69jge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xhys69jge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:alaska" {...props}></Icon>
