<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc_uedx6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fc_uedx6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:axolotl" {...props}></Icon>
