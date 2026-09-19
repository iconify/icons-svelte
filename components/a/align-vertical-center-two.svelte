<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwp_z2i8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mwp_z2i8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:align-vertical-center-two" {...props}></Icon>
