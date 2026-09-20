<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/q7dv2p0mu.css';
import '../../css/a/amzjcutka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="q7dv2p0mu"/><path class="amzjcutka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:expand-more-square-duotone" {...props}></Icon>
