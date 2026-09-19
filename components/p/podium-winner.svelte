<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m70qi2bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m70qi2bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:podium-winner" {...props}></Icon>
