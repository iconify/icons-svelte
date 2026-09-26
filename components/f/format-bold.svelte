<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/d12fgu-ud.css';
import '../../css/e/ercpunbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="d12fgu-ud"/><path vector-effect="non-scaling-stroke" class="ercpunbkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:format-bold" {...props}></Icon>
