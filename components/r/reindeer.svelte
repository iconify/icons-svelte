<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kokfi0b9c.css';
import '../../css/g/g4wcdukcc.css';
import '../../css/z/zoclu7wtg.css';
import '../../css/o/o06sic7wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kokfi0b9c"/><path class="g4wcdukcc"/><path class="wm-a zoclu7wtg"/><path class="o06sic7wt wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:reindeer" {...props}></Icon>
