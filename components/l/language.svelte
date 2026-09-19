<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kko_rr_sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kko_rr_sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:language" {...props}></Icon>
