<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/p6-k_8z1s.css';
import '../../css/j/jqn-to-yb.css';
import '../../css/l/le6y6pbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p6-k_8z1s"/><path class="jqn-to-yb"/><path class="le6y6pbtm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:clock3" {...props}></Icon>
