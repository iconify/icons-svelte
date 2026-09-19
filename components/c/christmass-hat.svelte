<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emduyp3ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="emduyp3ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:christmass-hat" {...props}></Icon>
