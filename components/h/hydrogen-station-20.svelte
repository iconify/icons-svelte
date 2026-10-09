<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iixfqsbra.css';
import '../../css/h/h0lo410vx.css';
import '../../css/m/mt37ukw5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iixfqsbra"/><path class="h0lo410vx"/><path class="mt37ukw5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-station-20" {...props}></Icon>
