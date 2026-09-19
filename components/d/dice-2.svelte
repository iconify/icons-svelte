<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlm1qqb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="rlm1qqb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:dice-2" {...props}></Icon>
