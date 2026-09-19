<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/dsdw4zbiz.css';
import '../../css/k/k4ub4p2ey.css';
import '../../css/b/bzxe9qa1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dsdw4zbiz"/><path class="k4ub4p2ey"/><path class="bzxe9qa1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:reload" {...props}></Icon>
