<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdp-0be3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xdp-0be3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:dagger-knife" {...props}></Icon>
