<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv36e_oum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="bv36e_oum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:clapboard-play" {...props}></Icon>
