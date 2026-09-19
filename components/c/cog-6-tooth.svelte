<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/m5md0gb6l.css';
import '../../css/t/tl_x59b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m5md0gb6l"/><path class="tl_x59b9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cog-6-tooth" {...props}></Icon>
