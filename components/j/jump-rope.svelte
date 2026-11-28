<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vp4kqio0x.css';
import '../../css/o/oc_v8ccyt.css';
import '../../css/p/p4pqdhbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vp4kqio0x"/><path class="oc_v8ccyt"/><path class="p4pqdhbxo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:jump-rope" {...props}></Icon>
