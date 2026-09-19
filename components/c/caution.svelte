<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/z/z8_mqecnt.css';
import '../../css/y/ydag_ubap.css';
import '../../css/o/oe_umpfom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="z8_mqecnt"/><path class="ydag_ubap"/><path class="oe_umpfom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:caution" {...props}></Icon>
