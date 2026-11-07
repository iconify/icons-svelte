<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/snto2-zvc.css';
import '../../css/w/wg8azcbhn.css';
import '../../css/h/hyjgutf1e.css';
import '../../css/f/f0g-urbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="snto2-zvc"/><path class="wg8azcbhn"/><path class="hyjgutf1e"/><path class="f0g-urbji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-code-line-duotone" {...props}></Icon>
