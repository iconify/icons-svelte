<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfm2d7bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cfm2d7bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:activity" {...props}></Icon>
