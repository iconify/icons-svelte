<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4i0zhp8u.css';
import '../../css/z/zhkqvsbwg.css';
import '../../css/f/f45da2b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w4i0zhp8u"/><path class="zhkqvsbwg"/><path class="f45da2b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-monitor-48-bold" {...props}></Icon>
