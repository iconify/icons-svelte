<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/j4zrhw3ad.css';
import '../../css/u/uttk3rw3q.css';
import '../../css/x/x_i_7_eop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="j4zrhw3ad"/><path class="uttk3rw3q"/><path class="x_i_7_eop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:composition-paronama-horizontal" {...props}></Icon>
