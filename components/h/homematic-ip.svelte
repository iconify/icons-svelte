<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqm2u1pft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rqm2u1pft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homematic-ip" {...props}></Icon>
