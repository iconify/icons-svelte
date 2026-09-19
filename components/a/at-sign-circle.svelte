<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/d5j13pb9q.css';
import '../../css/q/q2y25-y2o.css';
import '../../css/g/g9bey28zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d5j13pb9q"/><path class="q2y25-y2o"/><path class="g9bey28zn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:at-sign-circle" {...props}></Icon>
