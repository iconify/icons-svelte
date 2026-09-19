<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/ju9pfcbbq.css';
import '../../css/l/l_982k12n.css';
import '../../css/m/mnx3azbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ju9pfcbbq"/><path class="l_982k12n"/><path class="mnx3azbnn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gps-disconnected" {...props}></Icon>
