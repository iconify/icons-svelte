<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5wd7w_ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="k5wd7w_ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:glasses-outline" {...props}></Icon>
