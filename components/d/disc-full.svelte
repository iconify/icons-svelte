<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkjmmss5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="fkjmmss5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:disc-full" {...props}></Icon>
