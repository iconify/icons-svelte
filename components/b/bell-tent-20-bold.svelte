<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syjjg5boi.css';
import '../../css/q/qb-anoa-e.css';
import '../../css/l/l4lb-ym4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="syjjg5boi"/><path class="qb-anoa-e"/><path class="l4lb-ym4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-tent-20-bold" {...props}></Icon>
