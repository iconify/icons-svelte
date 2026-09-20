<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og140ebiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="og140ebiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:arrow-down" {...props}></Icon>
