<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuj184buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cuj184buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dji-logbook-light" {...props}></Icon>
