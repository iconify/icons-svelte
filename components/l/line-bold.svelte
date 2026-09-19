<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahorj_tjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ahorj_tjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:line-bold" {...props}></Icon>
