<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy2r1xdnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sy2r1xdnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jawbone" {...props}></Icon>
