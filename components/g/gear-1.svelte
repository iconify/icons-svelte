<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjeto3wbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="yjeto3wbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:gear-1" {...props}></Icon>
