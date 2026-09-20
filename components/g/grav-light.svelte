<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgy81lbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sgy81lbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grav-light" {...props}></Icon>
