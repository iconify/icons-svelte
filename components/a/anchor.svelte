<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/dr81gjbdd.css';
import '../../css/h/h4_frbcfb.css';
import '../../css/q/qmhuddb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dr81gjbdd"/><circle class="h4_frbcfb"/><path class="qmhuddb0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:anchor" {...props}></Icon>
