<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuvdc2bma.css';
import '../../css/w/ww4ol3fvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yuvdc2bma"/><path class="ww4ol3fvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oscilloscope-48" {...props}></Icon>
