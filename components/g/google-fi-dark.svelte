<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq1hv3m9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nq1hv3m9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-fi-dark" {...props}></Icon>
