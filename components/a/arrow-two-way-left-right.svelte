<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcxncr7km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="xcxncr7km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-two-way-left-right" {...props}></Icon>
