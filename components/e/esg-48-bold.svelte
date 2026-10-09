<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4447fbqf.css';
import '../../css/v/vqj7n5bos.css';
import '../../css/m/m7ecu8bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w4447fbqf"/><path class="vqj7n5bos"/><path class="m7ecu8bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:esg-48-bold" {...props}></Icon>
