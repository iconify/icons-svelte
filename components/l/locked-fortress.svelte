<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4znhhbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c4znhhbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:locked-fortress" {...props}></Icon>
