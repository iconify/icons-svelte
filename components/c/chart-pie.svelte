<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx8wwcc3r.css';
import '../../css/m/mb8xl_g2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nx8wwcc3r"/><path class="mb8xl_g2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chart-pie" {...props}></Icon>
