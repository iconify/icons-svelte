<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crh93bt4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="crh93bt4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fire-1-duo" {...props}></Icon>
