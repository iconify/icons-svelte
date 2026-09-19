<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhmzo7qrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bhmzo7qrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rocket" {...props}></Icon>
