<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu10s8xbg.css';
import '../../css/l/lnj0vzkpp.css';
import '../../css/e/e8x7bixqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fu10s8xbg"/><path class="lnj0vzkpp"/><path class="e8x7bixqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flashlight-48" {...props}></Icon>
