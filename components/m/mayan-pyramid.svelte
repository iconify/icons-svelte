<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km26slbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="km26slbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mayan-pyramid" {...props}></Icon>
