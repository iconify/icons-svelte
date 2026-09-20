<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9g2p8bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l9g2p8bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cargobike-and-dollar" {...props}></Icon>
