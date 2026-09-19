<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5te_76-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a5te_76-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:basket" {...props}></Icon>
