<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi8hjkbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pi8hjkbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:down-circle-outline" {...props}></Icon>
