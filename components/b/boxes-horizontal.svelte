<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwgcybb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mwgcybb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:boxes-horizontal" {...props}></Icon>
