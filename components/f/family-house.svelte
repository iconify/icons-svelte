<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr5js-58t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jr5js-58t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:family-house" {...props}></Icon>
