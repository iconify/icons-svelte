<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn4nbmbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rn4nbmbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:immich-kiosk-dark" {...props}></Icon>
