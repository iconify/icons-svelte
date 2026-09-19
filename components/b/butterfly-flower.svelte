<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqm7ajblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vqm7ajblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:butterfly-flower" {...props}></Icon>
