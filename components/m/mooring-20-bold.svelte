<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdy4ipb5m.css';
import '../../css/s/swkeh7byr.css';
import '../../css/z/zjjlddhpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zdy4ipb5m"/><path class="swkeh7byr"/><path class="zjjlddhpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mooring-20-bold" {...props}></Icon>
