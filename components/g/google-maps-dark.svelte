<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nac1dwsdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nac1dwsdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-maps-dark" {...props}></Icon>
