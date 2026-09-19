<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjvg-rh4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fjvg-rh4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:inner-self" {...props}></Icon>
