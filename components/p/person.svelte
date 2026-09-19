<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9l_web1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="a9l_web1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:person" {...props}></Icon>
