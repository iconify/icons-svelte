<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xkzigccsu.css';
import '../../css/j/jycvhms3v.css';
import '../../css/f/farndtbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xkzigccsu"/><path class="jycvhms3v"/><path class="farndtbyi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:flip-horizontal2" {...props}></Icon>
