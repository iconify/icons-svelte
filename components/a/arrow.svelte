<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6biv0w_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="c6biv0w_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow" {...props}></Icon>
