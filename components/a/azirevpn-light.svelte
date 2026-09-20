<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsfm2oczx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dsfm2oczx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:azirevpn-light" {...props}></Icon>
