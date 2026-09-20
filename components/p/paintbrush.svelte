<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/j8185sbtm.css';
import '../../css/z/ze-ddynnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j8185sbtm"/><path class="ze-ddynnn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paintbrush" {...props}></Icon>
