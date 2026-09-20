<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7e_i_bny.css';
import '../../css/w/wrnah39si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i7e_i_bny"/><path class="wrnah39si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glpi" {...props}></Icon>
