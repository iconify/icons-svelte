<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/uuheow30q.css';
import '../../css/q/qxcfuszic.css';
import '../../css/n/n5pbi4u5l.css';
import '../../css/n/naq3n-bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="uuheow30q"/><circle transform="matrix(-1 0 0 1 20.5 2)" class="qxcfuszic"/><path class="n5pbi4u5l"/><path class="naq3n-bhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:globe" {...props}></Icon>
