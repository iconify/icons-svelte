<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lews4bcdz.css';
import '../../css/r/rwgs81nbw.css';
import '../../css/o/ogdz0h5td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lews4bcdz"/><path class="rwgs81nbw"/><path class="ogdz0h5td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-sheets" {...props}></Icon>
