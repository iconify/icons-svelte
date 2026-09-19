<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfjdu186i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rfjdu186i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:open-treasure-chest" {...props}></Icon>
