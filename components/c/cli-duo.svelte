<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe88eacqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xe88eacqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cli-duo" {...props}></Icon>
