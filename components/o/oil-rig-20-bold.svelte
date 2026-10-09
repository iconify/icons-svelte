<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmn_z5chk.css';
import '../../css/p/pn2j6edzu.css';
import '../../css/f/fh6l5_iwg.css';
import '../../css/x/x6dmml5yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fmn_z5chk"/><path class="pn2j6edzu"/><path class="fh6l5_iwg"/><path class="x6dmml5yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-rig-20-bold" {...props}></Icon>
