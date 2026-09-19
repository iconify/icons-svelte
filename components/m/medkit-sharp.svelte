<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u98qkxxfj.css';
import '../../css/y/yy95vwqvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u98qkxxfj"/><path class="yy95vwqvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:medkit-sharp" {...props}></Icon>
