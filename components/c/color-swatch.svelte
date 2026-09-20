<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/z/z7o1plwou.css';
import '../../css/s/shv_7pb8m.css';
import '../../css/i/ih1z0vbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z7o1plwou"/><path class="shv_7pb8m"/><path class="ih1z0vbka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:color-swatch" {...props}></Icon>
