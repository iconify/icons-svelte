<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/cpxmezbkl.css';
import '../../css/u/uz_9y4b7u.css';
import '../../css/b/b19zuobxy.css';
import '../../css/p/p_0bzob4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="cpxmezbkl"/><path class="uz_9y4b7u"/><path class="b19zuobxy"/><path class="p_0bzob4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:covid19-virus-3" {...props}></Icon>
