<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t01p27bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t01p27bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fossil" {...props}></Icon>
