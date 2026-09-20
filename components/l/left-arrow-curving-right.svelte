<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx61_ej9h.css';
import '../../css/e/eyyhcy0xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fx61_ej9h"/><path class="eyyhcy0xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:left-arrow-curving-right" {...props}></Icon>
