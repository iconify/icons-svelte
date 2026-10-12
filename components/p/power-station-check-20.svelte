<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo5pkcblg.css';
import '../../css/m/mbm3jfb1f.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bo5pkcblg"/><path class="mbm3jfb1f"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-station-check-20" {...props}></Icon>
