<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr7vsjalr.css';
import '../../css/s/s0goipb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qr7vsjalr"/><rect class="s0goipb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:fog" {...props}></Icon>
