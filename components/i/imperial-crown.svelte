<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbpzvibfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pbpzvibfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:imperial-crown" {...props}></Icon>
