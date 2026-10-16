<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvufwdbic.css';
import '../../css/r/r_u1-tb8p.css';
import '../../css/h/h8ej8rbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kvufwdbic"/><path class="r_u1-tb8p"/><path class="h8ej8rbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cctv-20" {...props}></Icon>
