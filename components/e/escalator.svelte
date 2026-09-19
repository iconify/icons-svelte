<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmx3obbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qmx3obbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:escalator" {...props}></Icon>
