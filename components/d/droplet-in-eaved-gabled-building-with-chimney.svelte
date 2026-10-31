<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoqh6zybg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zoqh6zybg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-in-eaved-gabled-building-with-chimney" {...props}></Icon>
