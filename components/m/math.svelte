<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3ha7mwhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s3ha7mwhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:math" {...props}></Icon>
