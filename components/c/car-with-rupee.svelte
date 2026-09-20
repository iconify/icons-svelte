<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw7xf08hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cw7xf08hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-with-rupee" {...props}></Icon>
