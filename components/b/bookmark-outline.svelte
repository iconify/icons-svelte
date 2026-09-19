<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssmn0jj2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ssmn0jj2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bookmark-outline" {...props}></Icon>
