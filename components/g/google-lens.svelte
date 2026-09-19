<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/syqbndbck.css';
import '../../css/z/zdzqnkbnl.css';
import '../../css/f/fr_tmn9fp.css';
import '../../css/x/xtsrmvj7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="syqbndbck"/><path class="zdzqnkbnl"/><circle class="fr_tmn9fp"/><circle class="xtsrmvj7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:google-lens" {...props}></Icon>
