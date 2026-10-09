<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk88l0bcp.css';
import '../../css/o/o3m77ebsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yk88l0bcp"/><path class="o3m77ebsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alarm-clock-48" {...props}></Icon>
