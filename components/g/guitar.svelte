<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw8xe0b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jw8xe0b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:guitar" {...props}></Icon>
