<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex4r1ebmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ex4r1ebmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:directions-sign" {...props}></Icon>
