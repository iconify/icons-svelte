<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czwmjhe3n.css';
import '../../css/o/obc680b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="czwmjhe3n"/><path class="obc680b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:navaid-vortac" {...props}></Icon>
