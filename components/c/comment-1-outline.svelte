<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5zgcqb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="s5zgcqb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-1-outline" {...props}></Icon>
