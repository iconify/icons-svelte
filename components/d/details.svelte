<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf2u37s2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zf2u37s2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:details" {...props}></Icon>
