<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zckc6lblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="zckc6lblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:dice-1" {...props}></Icon>
