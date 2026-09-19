<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jz44n7b-f.css';
import '../../css/v/v63iznx0b.css';
import '../../css/m/mhmz4p10r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jz44n7b-f"/><path class="v63iznx0b"/><path class="mhmz4p10r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:locate-off" {...props}></Icon>
