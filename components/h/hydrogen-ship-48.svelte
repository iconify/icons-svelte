<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r30vy4y7i.css';
import '../../css/f/frzyvi6ro.css';
import '../../css/f/fj1_tccay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r30vy4y7i"/><path class="frzyvi6ro"/><path class="fj1_tccay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-ship-48" {...props}></Icon>
