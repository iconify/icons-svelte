<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvr0gmblg.css';
import '../../css/o/od6unwbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xvr0gmblg"/><path class="od6unwbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:keyboard" {...props}></Icon>
