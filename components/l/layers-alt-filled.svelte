<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k3m5n3c2p.css';
import '../../css/p/pqyg4ok7s.css';
import '../../css/z/z-7pz9x4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k3m5n3c2p"/><path class="pqyg4ok7s"/><path class="z-7pz9x4k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:layers-alt-filled" {...props}></Icon>
