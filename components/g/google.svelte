<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh7jpabfb.css';
import '../../css/g/gak2xbgdu.css';
import '../../css/h/hs9m8_bbv.css';
import '../../css/b/bqa1tob7t.css';
import '../../css/m/mt44fjb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xh7jpabfb"/><path class="gak2xbgdu"/><path class="hs9m8_bbv"/><path class="bqa1tob7t"/><path class="mt44fjb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:google" {...props}></Icon>
