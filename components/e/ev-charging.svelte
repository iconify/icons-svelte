<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bszj431is.css';
import '../../css/s/st2v-vblh.css';
import '../../css/l/lfk3ytbtu.css';
import '../../css/r/rphlimb5e.css';
import '../../css/m/mcz9ghbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bszj431is"/><path class="st2v-vblh"/><path class="lfk3ytbtu"/><path class="rphlimb5e"/><path class="mcz9ghbyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ev-charging" {...props}></Icon>
