<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk5u4qb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yk5u4qb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bench-duo" {...props}></Icon>
