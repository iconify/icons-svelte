<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmdh8w37g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="lmdh8w37g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:candy-stick" {...props}></Icon>
