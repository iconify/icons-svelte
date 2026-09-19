<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hqvb99byo.css';
import '../../css/c/c73e0yd1g.css';
import '../../css/r/rp2ocszvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hqvb99byo"/><path class="c73e0yd1g"/><path class="rp2ocszvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:id-card-lanyard" {...props}></Icon>
