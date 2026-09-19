<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s35u49yim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s35u49yim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:retro-controller" {...props}></Icon>
