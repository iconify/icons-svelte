<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7gon1bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c7gon1bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:immich-kiosk-light" {...props}></Icon>
