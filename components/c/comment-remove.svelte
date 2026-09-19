<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k74mtmcak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="k74mtmcak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-remove" {...props}></Icon>
