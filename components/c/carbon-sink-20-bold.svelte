<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlrq1pb6a.css';
import '../../css/q/qiqf2wm_a.css';
import '../../css/a/artzn1ocz.css';
import '../../css/m/mlxt40bpy.css';
import '../../css/n/nw-12wbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zlrq1pb6a"/><path class="qiqf2wm_a"/><path class="artzn1ocz"/><path class="mlxt40bpy"/><path class="nw-12wbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-sink-20-bold" {...props}></Icon>
