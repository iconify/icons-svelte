<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztli60bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ztli60bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:colombian-statue" {...props}></Icon>
