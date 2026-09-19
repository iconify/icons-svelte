<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh8ou-bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oh8ou-bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:end-page" {...props}></Icon>
