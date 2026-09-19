<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxpo5pboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wxpo5pboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:monkey" {...props}></Icon>
