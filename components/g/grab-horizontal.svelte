<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tswl3pbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tswl3pbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:grab-horizontal" {...props}></Icon>
