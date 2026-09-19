<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osfwb3bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="osfwb3bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:diamond-hard" {...props}></Icon>
