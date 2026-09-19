<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkf3q2s5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="mkf3q2s5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:film" {...props}></Icon>
