<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9_3scbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s9_3scbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:m-duo" {...props}></Icon>
