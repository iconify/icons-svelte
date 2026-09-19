<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bmvtfmy4l.css';
import '../../css/z/zut5arb6z.css';
import '../../css/w/wuim45b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bmvtfmy4l"/><path class="zut5arb6z"/><path class="wuim45b6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:doctor-01" {...props}></Icon>
