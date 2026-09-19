<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvq76tm2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mvq76tm2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:rectangular-vertebra" {...props}></Icon>
