<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_xhezbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i_xhezbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:annotation" {...props}></Icon>
