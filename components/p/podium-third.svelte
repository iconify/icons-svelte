<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw4uzcfbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mw4uzcfbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:podium-third" {...props}></Icon>
