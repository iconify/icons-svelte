<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/p/pe5iwv8nt.css';
import '../../css/o/o0o9wu-8v.css';
import '../../css/d/ddyhhlb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="pe5iwv8nt"/><path class="o0o9wu-8v"/><path class="ddyhhlb-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:eraser" {...props}></Icon>
