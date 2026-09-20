<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azc14govv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="azc14govv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-drive-dark" {...props}></Icon>
