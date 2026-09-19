<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er3n1379x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="er3n1379x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:caret" {...props}></Icon>
