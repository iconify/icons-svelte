<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek__51g7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="ek__51g7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:horse-shoe" {...props}></Icon>
