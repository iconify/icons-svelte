<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/elti8xbhv.css';
import '../../css/f/fwwvtv5go.css';
import '../../css/e/e-5oirana.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="elti8xbhv"/><path class="fwwvtv5go"/><path class="e-5oirana"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:blend" {...props}></Icon>
