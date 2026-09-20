<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dah24j1fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dah24j1fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:airboat-on-water" {...props}></Icon>
