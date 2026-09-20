<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pp77qjbwg.css';
import '../../css/q/qinvizbyq.css';
import '../../css/t/tkx6_bb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pp77qjbwg"/><path class="qinvizbyq"/><path class="tkx6_bb7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:parachute-drop-flat" {...props}></Icon>
