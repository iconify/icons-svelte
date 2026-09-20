<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu_idsbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uu_idsbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nordvpn" {...props}></Icon>
