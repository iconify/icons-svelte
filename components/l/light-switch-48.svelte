<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie-wxdblp.css';
import '../../css/t/tqdfodbmv.css';
import '../../css/p/p8s_xtbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ie-wxdblp"/><path class="tqdfodbmv"/><path class="p8s_xtbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:light-switch-48" {...props}></Icon>
