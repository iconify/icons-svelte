<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag-b0_ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ag-b0_ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lava" {...props}></Icon>
