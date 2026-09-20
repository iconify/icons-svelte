<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3_bsufwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q3_bsufwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:miniature-railway-track" {...props}></Icon>
