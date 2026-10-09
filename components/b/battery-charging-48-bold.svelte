<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmtj78bqh.css';
import '../../css/g/gzrd91bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cmtj78bqh"/><path class="gzrd91bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-charging-48-bold" {...props}></Icon>
