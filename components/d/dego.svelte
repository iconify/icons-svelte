<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku5-asgud.css';
import '../../css/h/hy5jsbbuj.css';
import '../../css/t/t32f0z35j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku5-asgud"/><path class="hy5jsbbuj"/><path class="t32f0z35j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dego" {...props}></Icon>
