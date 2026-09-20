<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3mdx591i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u3mdx591i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:drawing-document-filled" {...props}></Icon>
