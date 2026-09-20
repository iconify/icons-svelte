<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs6p-wb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rs6p-wb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:distribute-horizontal-solid" {...props}></Icon>
