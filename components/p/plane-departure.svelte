<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpuo_eyje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jpuo_eyje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:plane-departure" {...props}></Icon>
