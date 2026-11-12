<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obtzdzkzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="obtzdzkzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-cloud-dark" {...props}></Icon>
