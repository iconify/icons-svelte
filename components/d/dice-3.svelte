<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbnhksbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bbnhksbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:dice-3" {...props}></Icon>
