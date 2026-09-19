<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uymofrb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uymofrb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:planks" {...props}></Icon>
