<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b188s4buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b188s4buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:key-card" {...props}></Icon>
