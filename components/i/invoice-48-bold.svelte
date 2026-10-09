<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_pz3rxhk.css';
import '../../css/g/g2v90yuhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y_pz3rxhk"/><path class="g2v90yuhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:invoice-48-bold" {...props}></Icon>
