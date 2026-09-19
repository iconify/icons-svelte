<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y993d1bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="y993d1bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:coconut" {...props}></Icon>
