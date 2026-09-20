<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/q08khjbwt.css';
import '../../css/j/jc6w6-bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q08khjbwt"/><rect transform="matrix(0 -1 -1 0 18.5 15)" class="jc6w6-bos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:center-vertical" {...props}></Icon>
