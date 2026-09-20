<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/ld5x_6a-q.css';
import '../../css/h/h8g36l7qt.css';
import '../../css/i/i8vpebqdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ld5x_6a-q"/><path class="h8g36l7qt"/><path class="i8vpebqdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:print" {...props}></Icon>
