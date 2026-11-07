<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/br4_5duwz.css';
import '../../css/i/iexlgo4zk.css';
import '../../css/w/wprdp0m6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="br4_5duwz"/><path class="iexlgo4zk"/><path class="wprdp0m6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playback-speed-line-duotone" {...props}></Icon>
