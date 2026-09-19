<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im916tbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="im916tbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bowl-spiral" {...props}></Icon>
