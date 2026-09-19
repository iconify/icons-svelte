<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wos7l5pvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wos7l5pvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:overlord-helm" {...props}></Icon>
