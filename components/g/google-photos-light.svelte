<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3w52bb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d3w52bb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-photos-light" {...props}></Icon>
