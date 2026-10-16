<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c93ue0bjc.css';
import '../../css/c/c47fazbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c93ue0bjc"/><path class="c47fazbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ratchet-20-bold" {...props}></Icon>
