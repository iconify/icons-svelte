<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkry5yh6w.css';
import '../../css/v/vt7mt9-ct.css';
import '../../css/w/wl8gimjuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bkry5yh6w"/><path class="vt7mt9-ct"/><path class="wl8gimjuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:laser-level-48" {...props}></Icon>
