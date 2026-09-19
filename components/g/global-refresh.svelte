<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/ffrak0b0s.css';
import '../../css/n/nqrwakdsg.css';
import '../../css/q/qg4l4xbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ffrak0b0s"/><path class="nqrwakdsg"/><path class="qg4l4xbso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:global-refresh" {...props}></Icon>
