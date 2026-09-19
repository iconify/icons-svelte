<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2tydryof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y2tydryof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:airtight-hatch" {...props}></Icon>
