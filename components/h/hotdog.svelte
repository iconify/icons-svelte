<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9dxdtb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u9dxdtb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hotdog" {...props}></Icon>
