<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seho2dbyy.css';
import '../../css/w/wmbs3e3ue.css';
import '../../css/g/gikfybcho.css';
import '../../css/j/jc-p_wbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="seho2dbyy"/><path class="wmbs3e3ue"/><path class="gikfybcho"/><path class="jc-p_wbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-heater-48-bold" {...props}></Icon>
