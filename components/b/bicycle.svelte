<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/t/too0zm2ef.css';
import '../../css/r/rda75p-5s.css';
import '../../css/y/yzpjxzhlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="too0zm2ef"/><path class="rda75p-5s"/><path class="yzpjxzhlg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bicycle" {...props}></Icon>
