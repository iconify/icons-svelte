<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t6a7bkb4b.css';
import '../../css/t/t4n5mvw8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="t6a7bkb4b"/><path vector-effect="non-scaling-stroke" class="t4n5mvw8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:audio" {...props}></Icon>
