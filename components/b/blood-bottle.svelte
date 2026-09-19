<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qorhmmb2p.css';
import '../../css/p/pe7dhubax.css';
import '../../css/s/sxlhkwblw.css';
import '../../css/s/skr4s9e3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qorhmmb2p"/><path class="pe7dhubax"/><path class="sxlhkwblw"/><path class="skr4s9e3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:blood-bottle" {...props}></Icon>
