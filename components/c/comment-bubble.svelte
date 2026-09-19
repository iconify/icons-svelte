<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqj8fxb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1600};
const content = `<path class="nqj8fxb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:comment-bubble" {...props}></Icon>
