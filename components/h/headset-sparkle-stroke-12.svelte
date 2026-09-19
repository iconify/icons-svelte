<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v--xoo9qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="v--xoo9qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:headset-sparkle-stroke-12" {...props}></Icon>
