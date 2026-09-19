<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdlztobds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cdlztobds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-compress-quad" {...props}></Icon>
