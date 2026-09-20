<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tunlaubxi.css';
import '../../css/d/da5se5sef.css';
import '../../css/h/h01ydvy9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tunlaubxi"/><path class="da5se5sef"/><path class="h01ydvy9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ipfs-dark" {...props}></Icon>
