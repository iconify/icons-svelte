<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qs5th2sbp.css';
import '../../css/j/j3zc7kn1m.css';
import '../../css/x/x3yzpi80d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="qs5th2sbp"/><path class="j3zc7kn1m"/><path class="x3yzpi80d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:eye-slash" {...props}></Icon>
