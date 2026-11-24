<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0dij1bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="r0dij1bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:handshake-20-solid" {...props}></Icon>
