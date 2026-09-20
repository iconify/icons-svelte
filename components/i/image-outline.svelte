<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtc0q9bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dtc0q9bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:image-outline" {...props}></Icon>
