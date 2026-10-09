<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj0lqmb_y.css';
import '../../css/t/t8icqb2ug.css';
import '../../css/a/abqew6ljc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rj0lqmb_y"/><path class="t8icqb2ug"/><path class="abqew6ljc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lng-ship-20" {...props}></Icon>
