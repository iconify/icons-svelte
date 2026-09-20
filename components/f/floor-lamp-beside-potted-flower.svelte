<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu589o37q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mu589o37q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:floor-lamp-beside-potted-flower" {...props}></Icon>
