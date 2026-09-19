<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8v63iu0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h8v63iu0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bug" {...props}></Icon>
