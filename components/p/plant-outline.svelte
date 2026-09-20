<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc3muq5bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lc3muq5bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:plant-outline" {...props}></Icon>
