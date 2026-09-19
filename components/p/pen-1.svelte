<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qal-z721q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="qal-z721q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pen-1" {...props}></Icon>
