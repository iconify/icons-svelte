<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s340dhbaz.css';
import '../../css/f/fr5_r8b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s340dhbaz"/><path class="fr5_r8b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-vpn-dark" {...props}></Icon>
