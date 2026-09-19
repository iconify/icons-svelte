<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/in0jghbyd.css';
import '../../css/a/ardd_2b9b.css';
import '../../css/y/ya7jsccar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="in0jghbyd"/><path class="ardd_2b9b"/><path class="ya7jsccar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:master-card" {...props}></Icon>
