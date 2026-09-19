<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg0dw4z7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sg0dw4z7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:front-teeth" {...props}></Icon>
