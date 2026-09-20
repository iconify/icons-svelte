<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek2b1yb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ek2b1yb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:blazor" {...props}></Icon>
