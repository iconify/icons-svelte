<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itb5q2b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="itb5q2b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:plane-duo" {...props}></Icon>
