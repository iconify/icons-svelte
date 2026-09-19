<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt9ixm04t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nt9ixm04t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ant" {...props}></Icon>
