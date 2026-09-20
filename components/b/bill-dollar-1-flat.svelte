<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/k6mo8actu.css';
import '../../css/h/hq_6i5iyq.css';
import '../../css/y/ywareo_of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="k6mo8actu"/><path class="hq_6i5iyq"/><path class="ywareo_of"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:bill-dollar-1-flat" {...props}></Icon>
