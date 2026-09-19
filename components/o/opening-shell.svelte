<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9u4l7btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n9u4l7btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:opening-shell" {...props}></Icon>
