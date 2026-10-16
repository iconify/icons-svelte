<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2spr2bve.css';
import '../../css/x/xlfcvcr0c.css';
import '../../css/q/q7ailzblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f2spr2bve"/><path class="xlfcvcr0c"/><path class="q7ailzblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ceiling-light-48" {...props}></Icon>
