<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzmrovd6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yzmrovd6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:person-talk" {...props}></Icon>
