<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/a-wf-ib2y.css';
import '../../css/j/jc6w6-bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-wf-ib2y"/><rect transform="matrix(-1 0 0 1 15 5.5)" class="jc6w6-bos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:center-horizontal" {...props}></Icon>
