<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy2bf7d2l.css';
import '../../css/x/xr0hl1ndv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xy2bf7d2l"/><path class="xr0hl1ndv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-quality-20" {...props}></Icon>
