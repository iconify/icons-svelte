<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yda_7p-6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yda_7p-6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-draw" {...props}></Icon>
