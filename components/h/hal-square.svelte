<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofdlllb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ofdlllb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:hal-square" {...props}></Icon>
