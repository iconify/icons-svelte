<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjku5iuiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wjku5iuiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:circular-sawblade" {...props}></Icon>
