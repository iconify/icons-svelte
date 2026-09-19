<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d28u-tckq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d28u-tckq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:brasero" {...props}></Icon>
