<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/n/n51hvo05m.css';
import '../../css/p/pir0p8iya.css';
import '../../css/x/x5__mybwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n51hvo05m"/><rect class="pir0p8iya"/><path class="x5__mybwz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:progress-bar" {...props}></Icon>
