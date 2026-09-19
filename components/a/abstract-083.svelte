<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrcy5xw5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mrcy5xw5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-083" {...props}></Icon>
