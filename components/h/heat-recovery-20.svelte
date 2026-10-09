<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re19_f2ye.css';
import '../../css/u/um6ozge3g.css';
import '../../css/r/rcnrracia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="re19_f2ye"/><path class="um6ozge3g"/><path class="rcnrracia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-recovery-20" {...props}></Icon>
