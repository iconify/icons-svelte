<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3k9_ypge.css';
import '../../css/q/q_ao3jb5h.css';
import '../../css/q/qjx-16ssr.css';
import '../../css/i/i1g66_y5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f3k9_ypge"/><path class="q_ao3jb5h"/><path class="qjx-16ssr"/><path class="i1g66_y5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-tractor-48" {...props}></Icon>
