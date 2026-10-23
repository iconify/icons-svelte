<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/k/kxgqrsb3g.css';
import '../../css/a/ab06w6wfc.css';
import '../../css/h/hv6qyvkuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="kxgqrsb3g"/><path class="ab06w6wfc"/><path class="hv6qyvkuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:bandage" {...props}></Icon>
