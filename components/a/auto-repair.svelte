<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz84-d1xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bz84-d1xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:auto-repair" {...props}></Icon>
