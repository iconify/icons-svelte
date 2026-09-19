<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqr2403_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qqr2403_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dragon-spiral" {...props}></Icon>
