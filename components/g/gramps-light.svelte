<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq5ztorps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iq5ztorps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gramps-light" {...props}></Icon>
