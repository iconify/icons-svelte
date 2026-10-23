<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f1rc_1bfm.css';
import '../../css/g/gy4bdabyq.css';
import '../../css/u/ulwbbn_2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f1rc_1bfm"/><path class="gy4bdabyq"/><path class="ulwbbn_2k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-fading-play-duotone" {...props}></Icon>
