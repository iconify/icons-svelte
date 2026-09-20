<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwuetm4pl.css';
import '../../css/c/cyucoabfv.css';
import '../../css/t/tsi3labku.css';
import '../../css/g/gnqkz_bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rwuetm4pl"/><path class="cyucoabfv"/><path class="tsi3labku"/><path class="gnqkz_bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dosvault-dark" {...props}></Icon>
