<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p86kmy3qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p86kmy3qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-question-bold" {...props}></Icon>
