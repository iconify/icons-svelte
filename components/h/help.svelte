<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkyg13wqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkyg13wqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:help" {...props}></Icon>
