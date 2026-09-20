<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu2ujfbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xu2ujfbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flush-curb-with-exclamation-point" {...props}></Icon>
