<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amf5304bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="amf5304bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:energise" {...props}></Icon>
