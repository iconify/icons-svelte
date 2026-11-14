<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/b_pl27b6t.css';
import '../../css/z/ziild8bri.css';
import '../../css/m/ml-yuzelm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b_pl27b6t"/><path class="ziild8bri"/><path class="ml-yuzelm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:money-not-found-03" {...props}></Icon>
