<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4bty4nye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k4bty4nye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:alabama" {...props}></Icon>
