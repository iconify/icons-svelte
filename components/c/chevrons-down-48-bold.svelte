<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-on1cbzr.css';
import '../../css/w/wzs-74bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z-on1cbzr"/><path class="wzs-74bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-down-48-bold" {...props}></Icon>
