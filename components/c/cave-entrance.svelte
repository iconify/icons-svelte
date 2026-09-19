<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwgbuvb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wwgbuvb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cave-entrance" {...props}></Icon>
