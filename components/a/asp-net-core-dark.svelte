<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8csb0gic.css';
import '../../css/m/m3dery5fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l8csb0gic"/><path class="m3dery5fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:asp-net-core-dark" {...props}></Icon>
