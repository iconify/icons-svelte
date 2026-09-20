<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/wjuoup6qs.css';
import '../../css/t/tazr0wunn.css';
import '../../css/j/j16pcib4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wjuoup6qs"/><path class="tazr0wunn"/><path class="j16pcib4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:convert-three-d-cube" {...props}></Icon>
