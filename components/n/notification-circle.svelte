<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/ix74hpb0f.css';
import '../../css/d/dicptfbfk.css';
import '../../css/x/xei8vkhxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ix74hpb0f"/><path class="dicptfbfk"/><path class="xei8vkhxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:notification-circle" {...props}></Icon>
