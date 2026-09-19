<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r38g2ac-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r38g2ac-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:king-ju-mask" {...props}></Icon>
