<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/ok6k5b6nb.css';
import '../../css/e/emdkxcbdp.css';
import '../../css/o/owc868bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ok6k5b6nb"/><path class="emdkxcbdp"/><path class="owc868bvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:covid-19-virus-pandemic-1" {...props}></Icon>
