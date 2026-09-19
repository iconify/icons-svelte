<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqubd6bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="kqubd6bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pill-bold" {...props}></Icon>
