<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlamg4bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hlamg4bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ice-skate" {...props}></Icon>
