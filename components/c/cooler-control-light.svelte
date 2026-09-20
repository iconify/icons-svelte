<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpmq7pbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rpmq7pbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cooler-control-light" {...props}></Icon>
