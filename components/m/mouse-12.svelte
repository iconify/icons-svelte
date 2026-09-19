<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/ws0weable.css';
import '../../css/p/pdmaa-4wh.css';
import '../../css/j/jcyhgg-5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ws0weable"/><path class="pdmaa-4wh"/><path class="jcyhgg-5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-12" {...props}></Icon>
