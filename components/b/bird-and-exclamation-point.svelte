<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe0s7db0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oe0s7db0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bird-and-exclamation-point" {...props}></Icon>
