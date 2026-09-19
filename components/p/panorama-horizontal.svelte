<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4i273b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y4i273b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:panorama-horizontal" {...props}></Icon>
