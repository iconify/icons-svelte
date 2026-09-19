<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd13eg0ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pd13eg0ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:align-horizontal-center-two" {...props}></Icon>
