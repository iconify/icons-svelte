<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtexm5bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rtexm5bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-067" {...props}></Icon>
