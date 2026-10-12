<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih35z4x5n.css';
import '../../css/l/l7s7xcc2s.css';
import '../../css/c/ckludqbvv.css';
import '../../css/e/e3y16ob3v.css';
import '../../css/y/ygtv74bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ih35z4x5n"/><path class="l7s7xcc2s"/><path class="ckludqbvv"/><path class="e3y16ob3v"/><path class="ygtv74bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-storage-alert-48-bold" {...props}></Icon>
