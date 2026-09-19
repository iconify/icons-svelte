<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d100xbbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d100xbbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mine-truck" {...props}></Icon>
