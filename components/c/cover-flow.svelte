<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/famlpk19j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="famlpk19j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cover-flow" {...props}></Icon>
