<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzraxzf0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fzraxzf0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:hammer" {...props}></Icon>
