<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klwxksbur.css';
import '../../css/p/pa_rqzygz.css';
import '../../css/a/au0y91bpr.css';
import '../../css/n/nsu45-bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="klwxksbur"/><path class="pa_rqzygz"/><path class="au0y91bpr"/><path transform="matrix(1.47345 0 0 1.55542 -73.182 -243.814)" class="nsu45-bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:bevyengine-wordmark" {...props}></Icon>
