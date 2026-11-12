<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcwrfsx8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dcwrfsx8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:orb" {...props}></Icon>
