<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/p8flmhbrr.css';
import '../../css/l/lsg8msbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="p8flmhbrr"/><path vector-effect="non-scaling-stroke" class="lsg8msbeo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:justify-space-evenly" {...props}></Icon>
