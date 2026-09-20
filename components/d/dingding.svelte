<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voqdh3b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="voqdh3b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:dingding" {...props}></Icon>
