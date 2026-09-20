<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn0u3gbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nn0u3gbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:artboard-outline" {...props}></Icon>
