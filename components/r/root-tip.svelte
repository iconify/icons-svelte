<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax5x1zbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ax5x1zbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:root-tip" {...props}></Icon>
