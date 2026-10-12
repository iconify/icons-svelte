<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozw6d3b3f.css';
import '../../css/h/h2bmrpbsg.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ozw6d3b3f"/><path class="h2bmrpbsg"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-check-20" {...props}></Icon>
