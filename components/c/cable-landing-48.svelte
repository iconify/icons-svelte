<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eilv5mbmy.css';
import '../../css/f/f_b1kumim.css';
import '../../css/r/r1ohr3b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eilv5mbmy"/><path class="f_b1kumim"/><path class="r1ohr3b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-landing-48" {...props}></Icon>
