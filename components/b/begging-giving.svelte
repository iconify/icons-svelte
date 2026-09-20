<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kzem0p7_u.css';
import '../../css/t/t0pymt0bq.css';
import '../../css/i/ikmve7dyu.css';
import '../../css/m/mxyg-1bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="kzem0p7_u"/><path class="t0pymt0bq"/><path class="ikmve7dyu"/><path class="mxyg-1bkp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:begging-giving" {...props}></Icon>
