<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiwh17hkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aiwh17hkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:moon-outline" {...props}></Icon>
