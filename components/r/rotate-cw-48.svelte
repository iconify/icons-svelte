<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crskxccsk.css';
import '../../css/t/t_o6wlbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="crskxccsk"/><path class="t_o6wlbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotate-cw-48" {...props}></Icon>
