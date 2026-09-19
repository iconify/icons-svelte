<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcyn1ccfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mcyn1ccfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:left-two" {...props}></Icon>
