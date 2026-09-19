<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/cgh6afzdr.css';
import '../../css/w/wr3ilibzg.css';
import '../../css/q/qg6wjyjbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cgh6afzdr"/><path class="wr3ilibzg"/><path class="qg6wjyjbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:keyframes-multiple" {...props}></Icon>
