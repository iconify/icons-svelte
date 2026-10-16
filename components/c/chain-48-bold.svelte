<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcazebc-h.css';
import '../../css/r/r09w33bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fcazebc-h"/><path class="r09w33bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chain-48-bold" {...props}></Icon>
