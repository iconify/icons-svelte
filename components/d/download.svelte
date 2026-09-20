<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhz9xx3hp.css';
import '../../css/w/wb8gpybsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dhz9xx3hp"/><path class="wb8gpybsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:download" {...props}></Icon>
