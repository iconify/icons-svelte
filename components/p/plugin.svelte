<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy8w9gs9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="wy8w9gs9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:plugin" {...props}></Icon>
