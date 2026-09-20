<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adrjpvbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="adrjpvbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:electrical-square-circuit-breaker-and-bolt" {...props}></Icon>
