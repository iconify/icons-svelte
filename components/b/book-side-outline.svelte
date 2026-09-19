<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgpptxj6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cgpptxj6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book-side-outline" {...props}></Icon>
