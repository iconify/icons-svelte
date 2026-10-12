<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_82bfbeu.css';
import '../../css/w/wl2ljnc3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c_82bfbeu"/><path class="wl2ljnc3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:function-48-bold" {...props}></Icon>
