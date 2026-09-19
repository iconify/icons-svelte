<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8xay6bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g8xay6bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:claymore-explosive" {...props}></Icon>
