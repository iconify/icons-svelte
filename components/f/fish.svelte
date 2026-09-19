<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rux_79ovi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rux_79ovi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:fish" {...props}></Icon>
