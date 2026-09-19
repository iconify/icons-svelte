<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs7-nlzox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qs7-nlzox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:evil-minion" {...props}></Icon>
