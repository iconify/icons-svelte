<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fscw49xbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fscw49xbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nest-birds" {...props}></Icon>
