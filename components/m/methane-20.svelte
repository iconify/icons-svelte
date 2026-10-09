<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd76aibix.css';
import '../../css/o/o6l1bjq5b.css';
import '../../css/v/vr6h6mb_x.css';
import '../../css/z/zll9itmnm.css';
import '../../css/f/f4i-1bbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vd76aibix"/><path class="o6l1bjq5b"/><path class="vr6h6mb_x"/><path class="zll9itmnm"/><path class="f4i-1bbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:methane-20" {...props}></Icon>
