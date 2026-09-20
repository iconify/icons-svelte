<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwu39txpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mwu39txpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bluesky" {...props}></Icon>
