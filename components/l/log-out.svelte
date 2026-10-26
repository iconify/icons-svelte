<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsg68bc0n.css';
import '../../css/p/p53aibb7y.css';
import '../../css/i/isx_m27xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="qsg68bc0n"><path class="p53aibb7y"/><path class="isx_m27xg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:log-out" {...props}></Icon>
