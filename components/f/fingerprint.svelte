<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/puo6m7bvm.css';
import '../../css/b/bmiu8w0sc.css';
import '../../css/c/cmsqj627t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="puo6m7bvm"/><path class="bmiu8w0sc"/><path class="cmsqj627t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fingerprint" {...props}></Icon>
