<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvg12-bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yvg12-bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bold-fill-12" {...props}></Icon>
