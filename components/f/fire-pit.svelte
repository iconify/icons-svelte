<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/rth5cebwd.css';
import '../../css/t/tq0hxla5z.css';
import '../../css/r/rq45kidda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rth5cebwd"/><path class="tq0hxla5z"/><path class="rq45kidda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:fire-pit" {...props}></Icon>
