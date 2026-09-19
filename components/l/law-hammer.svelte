<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwy89e47i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="iwy89e47i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:law-hammer" {...props}></Icon>
