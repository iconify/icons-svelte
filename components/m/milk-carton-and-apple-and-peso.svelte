<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu4ps270m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mu4ps270m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:milk-carton-and-apple-and-peso" {...props}></Icon>
