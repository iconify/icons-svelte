<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4evchbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b4evchbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:canoe" {...props}></Icon>
