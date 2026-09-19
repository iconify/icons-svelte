<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_ls7obax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="e_ls7obax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-spread-duo" {...props}></Icon>
