<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5ln-ibxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e5ln-ibxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:falling-eye" {...props}></Icon>
