<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9cx5cc5b.css';
import '../../css/l/lmjbu-ywi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f9cx5cc5b"/><path class="lmjbu-ywi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-20" {...props}></Icon>
