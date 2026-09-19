<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/dzc1y6b0m.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/y/yhkdl0bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="dzc1y6b0m"/><circle class="shu3xdl9q"/><path class="yhkdl0bgf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-web-browsing" {...props}></Icon>
