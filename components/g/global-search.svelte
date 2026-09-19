<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/ed3_dlb7r.css';
import '../../css/q/qg4l4xbso.css';
import '../../css/a/a6moqwkki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ed3_dlb7r"/><path class="qg4l4xbso"/><path class="a6moqwkki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:global-search" {...props}></Icon>
