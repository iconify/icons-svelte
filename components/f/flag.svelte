<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw9iszhry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hw9iszhry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:flag" {...props}></Icon>
