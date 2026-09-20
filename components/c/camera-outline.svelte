<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs83cbbpj.css';
import '../../css/x/xe_mok4yw.css';
import '../../css/t/tyubjgq6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hs83cbbpj"><path class="xe_mok4yw"/><path class="tyubjgq6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:camera-outline" {...props}></Icon>
