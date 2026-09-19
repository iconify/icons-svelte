<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuy7yly5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zuy7yly5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:incoming-rocket" {...props}></Icon>
