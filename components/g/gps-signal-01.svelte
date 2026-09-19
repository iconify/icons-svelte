<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l_982k12n.css';
import '../../css/o/o4oqigbmb.css';
import '../../css/n/ny9wgu8al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="l_982k12n"/><path class="o4oqigbmb"/><path class="ny9wgu8al"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gps-signal-01" {...props}></Icon>
