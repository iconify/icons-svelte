<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb2gx18ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eb2gx18ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-with-hiking-pole-wearing-backpack" {...props}></Icon>
