<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrgy8szvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rrgy8szvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:convict" {...props}></Icon>
