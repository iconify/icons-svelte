<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih1_q1b8g.css';
import '../../css/m/mllvz95kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ih1_q1b8g"/><path class="mllvz95kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:and-gate-20" {...props}></Icon>
