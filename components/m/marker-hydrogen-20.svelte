<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgjp5_b_u.css';
import '../../css/t/tznh2vbzh.css';
import '../../css/m/m7fctby7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wgjp5_b_u"/><path class="tznh2vbzh"/><path class="m7fctby7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-hydrogen-20" {...props}></Icon>
