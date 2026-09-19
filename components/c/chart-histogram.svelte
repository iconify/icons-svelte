<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1pgz2big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p1pgz2big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:chart-histogram" {...props}></Icon>
