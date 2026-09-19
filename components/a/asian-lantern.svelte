<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e59zbs5hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e59zbs5hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:asian-lantern" {...props}></Icon>
