<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5cz3ibue.css';
import '../../css/g/gk_j4gbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x5cz3ibue"/><path class="gk_j4gbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:microphone-off-fill-16" {...props}></Icon>
