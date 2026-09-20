<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-fvxvbsq.css';
import '../../css/f/fdzbfobsz.css';
import '../../css/y/yjd8i8vse.css';
import '../../css/w/wdhz7d8hl.css';
import '../../css/n/n_g3robjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-fvxvbsq"/><path class="fdzbfobsz"/><path class="yjd8i8vse"/><path class="wdhz7d8hl"/><path class="n_g3robjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-shopping" {...props}></Icon>
