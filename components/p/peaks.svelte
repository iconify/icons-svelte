<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umbjv2blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="umbjv2blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:peaks" {...props}></Icon>
