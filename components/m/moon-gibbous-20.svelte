<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suk0u9b4j.css';
import '../../css/p/pf11sko1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="suk0u9b4j"/><path class="pf11sko1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-gibbous-20" {...props}></Icon>
