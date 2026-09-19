<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0sww7bvb.css';
import '../../css/n/n25i1etik.css';
import '../../css/b/b6f16cc2l.css';
import '../../css/o/ox_vh_ycg.css';
import '../../css/h/hsl6dub9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0sww7bvb"/><path class="n25i1etik"/><path class="b6f16cc2l"/><path class="ox_vh_ycg"/><path class="hsl6dub9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-volume-off" {...props}></Icon>
