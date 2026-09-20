<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc4x_wb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tc4x_wb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chevron-up-small" {...props}></Icon>
