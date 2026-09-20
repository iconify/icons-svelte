<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/z/zdsdlcb9m.css';
import '../../css/i/is7m5ub9x.css';
import '../../css/c/c-8fi9pzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zdsdlcb9m"/><path class="is7m5ub9x"/><path class="c-8fi9pzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:location-user" {...props}></Icon>
