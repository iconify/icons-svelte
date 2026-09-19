<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jya-soblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jya-soblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-line-end-duo" {...props}></Icon>
