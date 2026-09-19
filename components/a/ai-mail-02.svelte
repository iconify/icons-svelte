<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/g/gdpq22bzn.css';
import '../../css/m/ma0e2kbll.css';
import '../../css/o/os5u60drp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="gdpq22bzn"/><path class="ma0e2kbll"/><path class="os5u60drp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-mail-02" {...props}></Icon>
