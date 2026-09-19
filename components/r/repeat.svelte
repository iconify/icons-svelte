<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5a9aobrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="c5a9aobrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:repeat" {...props}></Icon>
