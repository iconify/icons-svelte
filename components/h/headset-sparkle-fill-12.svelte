<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgykehbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dgykehbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:headset-sparkle-fill-12" {...props}></Icon>
